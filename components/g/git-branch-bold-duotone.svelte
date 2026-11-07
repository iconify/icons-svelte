<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpe08f7jm.css';
import '../../css/j/jj7xoyfhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpe08f7jm"/><path clip-rule="evenodd" class="jj7xoyfhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:git-branch-bold-duotone" {...props}></Icon>
