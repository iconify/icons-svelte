<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o38ht4b5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o38ht4b5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:flag-2-fill" {...props}></Icon>
