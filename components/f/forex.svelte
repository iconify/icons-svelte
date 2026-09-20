<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olzavh4ia.css';
import '../../css/w/wqvb8lb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olzavh4ia"/><path clip-rule="evenodd" class="wqvb8lb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:forex" {...props}></Icon>
