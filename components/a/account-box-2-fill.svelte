<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7uyqkbro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7uyqkbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:account-box-2-fill" {...props}></Icon>
