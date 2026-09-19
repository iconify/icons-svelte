<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl4vnpthx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bl4vnpthx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:building-alt-02-filled" {...props}></Icon>
