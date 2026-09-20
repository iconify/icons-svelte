<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwvee8bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwvee8bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:credit-card-x" {...props}></Icon>
