<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-qxuibhr.css';
import '../../css/l/lxtaj1b-t.css';
import '../../css/t/tx-n4du-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g-qxuibhr"/><path class="lxtaj1b-t"/><path class="tx-n4du-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-vuex-store-open" {...props}></Icon>
