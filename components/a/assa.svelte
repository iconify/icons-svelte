<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opi4shb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opi4shb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:assa" {...props}></Icon>
