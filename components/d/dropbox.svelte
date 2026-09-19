<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvnjtkb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nvnjtkb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:dropbox" {...props}></Icon>
