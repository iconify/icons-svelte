<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk7v8qlqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jk7v8qlqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rotate-right-05" {...props}></Icon>
