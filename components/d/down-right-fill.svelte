<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi0jf0b9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi0jf0b9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:down-right-fill" {...props}></Icon>
