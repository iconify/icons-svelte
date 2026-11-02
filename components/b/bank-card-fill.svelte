<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mamctmbrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mamctmbrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bank-card-fill" {...props}></Icon>
