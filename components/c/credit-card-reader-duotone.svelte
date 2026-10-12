<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o3ks6kk1v.css';
import '../../css/k/k09hkxgwo.css';
import '../../css/a/asyru8bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o3ks6kk1v"/><path class="k09hkxgwo"/><path class="asyru8bos"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:credit-card-reader-duotone" {...props}></Icon>
