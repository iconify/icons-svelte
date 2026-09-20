<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu31aqbef.css';
import '../../css/s/s1mar9bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fu31aqbef"/><path class="s1mar9bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:playlist" {...props}></Icon>
