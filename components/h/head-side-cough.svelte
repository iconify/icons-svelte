<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh0y2gb1s.css';
import '../../css/e/ebu-_wb0p.css';
import '../../css/q/qz5bn7pgu.css';
import '../../css/b/bupp6s2bh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="lh0y2gb1s"/><circle class="ebu-_wb0p"/><circle class="qz5bn7pgu"/><path class="bupp6s2bh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:head-side-cough" {...props}></Icon>
