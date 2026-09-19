<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snfofybnw.css';
import '../../css/e/e6l3g5bzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snfofybnw"/><path class="e6l3g5bzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:message-alt-edit" {...props}></Icon>
