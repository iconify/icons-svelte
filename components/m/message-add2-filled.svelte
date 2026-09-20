<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-moc8btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-moc8btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:message-add2-filled" {...props}></Icon>
