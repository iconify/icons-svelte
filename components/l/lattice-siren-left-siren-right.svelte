<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-7hzubuy.css';
import '../../css/b/bza6db8oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j-7hzubuy"/><path class="bza6db8oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:lattice-siren-left-siren-right" {...props}></Icon>
