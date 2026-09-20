<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-86ihbop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-86ihbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:design-tool-pencil-ruler" {...props}></Icon>
