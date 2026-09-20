<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6onf1bec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6onf1bec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:quote-fill" {...props}></Icon>
