<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm242wkvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sm242wkvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:layout-grid" {...props}></Icon>
