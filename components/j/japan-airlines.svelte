<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj4rqzjdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wj4rqzjdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:japan-airlines" {...props}></Icon>
