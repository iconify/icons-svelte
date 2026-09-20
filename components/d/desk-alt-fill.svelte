<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7fle5b6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u7fle5b6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:desk-alt-fill" {...props}></Icon>
