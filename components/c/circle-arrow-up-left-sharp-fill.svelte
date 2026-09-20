<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h29zzibek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h29zzibek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-arrow-up-left-sharp-fill" {...props}></Icon>
