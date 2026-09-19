<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezj3qtbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ezj3qtbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:app" {...props}></Icon>
