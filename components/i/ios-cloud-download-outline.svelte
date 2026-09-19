<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a66vcju6v.css';
import '../../css/j/jb9r22v3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a66vcju6v"/><path class="jb9r22v3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-cloud-download-outline" {...props}></Icon>
