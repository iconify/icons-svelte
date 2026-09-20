<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moh13gbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="moh13gbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:messages-fill" {...props}></Icon>
