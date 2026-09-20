<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiz_nbbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aiz_nbbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:ear-listen-sharp-fill" {...props}></Icon>
