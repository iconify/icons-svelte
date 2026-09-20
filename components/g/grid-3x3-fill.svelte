<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4fzh6b-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d4fzh6b-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grid-3x3-fill" {...props}></Icon>
