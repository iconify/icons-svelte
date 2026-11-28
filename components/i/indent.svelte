<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcd4nhlvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcd4nhlvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:indent" {...props}></Icon>
