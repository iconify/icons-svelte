<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txo1x1bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="txo1x1bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:chevron-right" {...props}></Icon>
