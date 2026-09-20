<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stzcg7bhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="stzcg7bhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:label-important-filled" {...props}></Icon>
