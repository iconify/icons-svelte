<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s03svacbz.css';
import '../../css/j/jwf99rbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s03svacbz"/><path class="jwf99rbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-icon-filled" {...props}></Icon>
