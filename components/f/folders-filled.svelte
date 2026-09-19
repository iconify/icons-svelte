<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k16xm7bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k16xm7bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:folders-filled" {...props}></Icon>
