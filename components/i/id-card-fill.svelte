<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8i3s3bzy.css';
import '../../css/b/bgzw1sbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8i3s3bzy"/><path class="bgzw1sbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:id-card-fill" {...props}></Icon>
