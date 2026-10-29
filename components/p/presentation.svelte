<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksor9la2b.css';
import '../../css/k/k77tf5bom.css';
import '../../css/s/svi179bkq.css';
import '../../css/p/pbw7u6bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksor9la2b wm-a"/><path class="k77tf5bom wm-k"/><path class="svi179bkq wm-a"/><path class="pbw7u6bac wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:presentation" {...props}></Icon>
