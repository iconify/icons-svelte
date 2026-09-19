<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghy9vobgd.css';
import '../../css/b/bqzzynbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ghy9vobgd"/><path class="bqzzynbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-flask-outline" {...props}></Icon>
