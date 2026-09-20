<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzzv-dbod.css';
import '../../css/v/v19mbwu8m.css';
import '../../css/p/pbaa7xb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzzv-dbod"/><path class="v19mbwu8m"/><path class="pbaa7xb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:kan" {...props}></Icon>
