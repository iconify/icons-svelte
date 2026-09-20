<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwf82ffby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jwf82ffby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:building-sharp-fill" {...props}></Icon>
