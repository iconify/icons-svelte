<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwoi71b8l.css';
import '../../css/j/jql0-8iqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iwoi71b8l"/><path class="jql0-8iqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipe-reducer-20" {...props}></Icon>
