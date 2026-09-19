<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3dh3ypqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p3dh3ypqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:menu-alt-02" {...props}></Icon>
