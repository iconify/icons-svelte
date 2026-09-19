<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci71hn2_l.css';
import '../../css/a/ae5r06sbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ci71hn2_l"/><path class="ae5r06sbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:ai" {...props}></Icon>
