<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spmf_h7bn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spmf_h7bn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:inductive-automation" {...props}></Icon>
