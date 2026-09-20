<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz83kzh_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iz83kzh_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:azurepipelines" {...props}></Icon>
