<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b26ky1b-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b26ky1b-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-arrow-u-turn-right-sharp-fill" {...props}></Icon>
