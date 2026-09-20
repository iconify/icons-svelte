<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7uq3ghml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q7uq3ghml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bitbucket-outline" {...props}></Icon>
