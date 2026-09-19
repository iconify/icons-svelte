<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egp4naccw.css';
import '../../css/j/jexl-dbou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="egp4naccw"/><path class="jexl-dbou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:numerical-sorting-12" {...props}></Icon>
