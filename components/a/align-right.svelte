<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i58rq-36d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i58rq-36d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:align-right" {...props}></Icon>
