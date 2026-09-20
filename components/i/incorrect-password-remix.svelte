<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-f7zs-ue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v-f7zs-ue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:incorrect-password-remix" {...props}></Icon>
