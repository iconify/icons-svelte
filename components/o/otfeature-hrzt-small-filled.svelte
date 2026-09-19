<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4v-gabjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="o4v-gabjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-hrzt-small-filled" {...props}></Icon>
