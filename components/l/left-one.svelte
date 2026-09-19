<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi856n_4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wi856n_4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:left-one" {...props}></Icon>
