<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl6wzybyg.css';
import '../../css/k/kvxqcabet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nl6wzybyg"/><path class="kvxqcabet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-bottom-open-bold" {...props}></Icon>
