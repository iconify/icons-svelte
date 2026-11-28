<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxm8t9inl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxm8t9inl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:clock-check" {...props}></Icon>
