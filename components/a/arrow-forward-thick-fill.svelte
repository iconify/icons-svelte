<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aae35_ljn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aae35_ljn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:arrow-forward-thick-fill" {...props}></Icon>
