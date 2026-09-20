<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufvn0ab1g.css';
import '../../css/g/gbeeqjbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufvn0ab1g"/><path class="gbeeqjbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:ellipses-vertical-circle" {...props}></Icon>
