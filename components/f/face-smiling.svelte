<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omyq3kh2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="omyq3kh2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:face-smiling" {...props}></Icon>
