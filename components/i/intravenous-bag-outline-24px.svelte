<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2m81sbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s2m81sbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:intravenous-bag-outline-24px" {...props}></Icon>
