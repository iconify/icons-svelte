<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dei_17bxy.css';
import '../../css/h/ht7052bix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dei_17bxy"/><path class="ht7052bix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:outbox" {...props}></Icon>
