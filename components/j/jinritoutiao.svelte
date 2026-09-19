<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_3qcrb_p.css';
import '../../css/k/kb-ng1w_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n_3qcrb_p"/><path clip-rule="evenodd" class="kb-ng1w_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:jinritoutiao" {...props}></Icon>
