<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdx4y4vma.css';
import '../../css/r/rslfarb6v.css';
import '../../css/h/h9hstt17t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdx4y4vma"/><path class="rslfarb6v"/><path class="h9hstt17t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:private-content-solid" {...props}></Icon>
