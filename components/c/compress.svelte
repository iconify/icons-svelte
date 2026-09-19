<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfwkytz5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="kfwkytz5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:compress" {...props}></Icon>
