<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogxoes63k.css';
import '../../css/z/zcqz9mbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogxoes63k"/><path class="zcqz9mbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-move-duotone" {...props}></Icon>
