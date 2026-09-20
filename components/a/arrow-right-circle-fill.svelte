<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnmqinbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gnmqinbhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:arrow-right-circle-fill" {...props}></Icon>
