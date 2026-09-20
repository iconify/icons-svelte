<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vql-jj_cu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vql-jj_cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:arrow-import" {...props}></Icon>
