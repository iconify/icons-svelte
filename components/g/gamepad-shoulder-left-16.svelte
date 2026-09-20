<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aieknlrza.css';
import '../../css/p/p-1znlk9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aieknlrza"/><path clip-rule="evenodd" class="p-1znlk9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:gamepad-shoulder-left-16" {...props}></Icon>
