<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8fbprehd.css';
import '../../css/u/u_bgapr5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8fbprehd"/><path clip-rule="evenodd" class="u_bgapr5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-cog-bold" {...props}></Icon>
