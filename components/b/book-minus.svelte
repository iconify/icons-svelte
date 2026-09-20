<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d93v-8biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d93v-8biw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:book-minus" {...props}></Icon>
