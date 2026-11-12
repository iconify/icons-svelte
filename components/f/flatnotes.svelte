<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcbi2lbyp.css';
import '../../css/p/pckj90bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kcbi2lbyp"/><path class="pckj90bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flatnotes" {...props}></Icon>
