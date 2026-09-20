<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-__p5b6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-__p5b6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:hard-drive-line" {...props}></Icon>
