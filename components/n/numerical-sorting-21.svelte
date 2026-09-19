<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egp4naccw.css';
import '../../css/x/xisz-8bbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="egp4naccw"/><path class="xisz-8bbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:numerical-sorting-21" {...props}></Icon>
