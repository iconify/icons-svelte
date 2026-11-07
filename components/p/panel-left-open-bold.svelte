<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_pkd94hu.css';
import '../../css/o/o-08tibye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j_pkd94hu"/><path class="o-08tibye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-left-open-bold" {...props}></Icon>
