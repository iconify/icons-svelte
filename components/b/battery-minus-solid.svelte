<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3kqxsbqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3kqxsbqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:battery-minus-solid" {...props}></Icon>
