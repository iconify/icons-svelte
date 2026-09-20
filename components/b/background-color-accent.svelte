<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7pao0m-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n7pao0m-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:background-color-accent" {...props}></Icon>
