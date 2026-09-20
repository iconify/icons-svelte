<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc5tmtbuk.css';
import '../../css/j/jb32k7b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tc5tmtbuk"/><path class="jb32k7b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:museum-filled" {...props}></Icon>
