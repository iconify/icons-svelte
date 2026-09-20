<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9s4n-b7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9s4n-b7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:fast-forward-sharp-fill" {...props}></Icon>
