<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqdxotbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqdxotbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-8-sharp" {...props}></Icon>
