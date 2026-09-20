<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye9nqmbve.css';
import '../../css/w/wo2kix3uq.css';
import '../../css/i/ijwz2bbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ye9nqmbve"/><path class="wo2kix3uq"/><path class="ijwz2bbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:add-bookmark" {...props}></Icon>
