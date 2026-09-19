<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxvnz6ymq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxvnz6ymq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:folder-arrow-down" {...props}></Icon>
