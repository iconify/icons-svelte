<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shbgs2bdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="shbgs2bdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:double-bookmark-remix" {...props}></Icon>
