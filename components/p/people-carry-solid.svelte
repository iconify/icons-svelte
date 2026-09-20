<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjwxeybpm.css';
import '../../css/i/ifjc3lcbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjwxeybpm"/><path class="ifjc3lcbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:people-carry-solid" {...props}></Icon>
