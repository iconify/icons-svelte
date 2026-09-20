<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b892889sj.css';
import '../../css/p/pc0n9-bvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b892889sj"/><path class="pc0n9-bvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:computer-chip-core-bold" {...props}></Icon>
