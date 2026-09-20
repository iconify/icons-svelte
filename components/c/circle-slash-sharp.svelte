<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrk_5v7yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrk_5v7yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-slash-sharp" {...props}></Icon>
