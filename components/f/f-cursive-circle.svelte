<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4acjnbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="h4acjnbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:f-cursive-circle" {...props}></Icon>
