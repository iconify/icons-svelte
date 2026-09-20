<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spnly9btv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spnly9btv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-commit-horizontal" {...props}></Icon>
