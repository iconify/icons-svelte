<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brs0dzbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brs0dzbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:changin-room-man" {...props}></Icon>
