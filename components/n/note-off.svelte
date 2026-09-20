<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh6-hzvzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jh6-hzvzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:note-off" {...props}></Icon>
