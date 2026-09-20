<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk7y_4b-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hk7y_4b-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-n" {...props}></Icon>
