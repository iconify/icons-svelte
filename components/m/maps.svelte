<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olwjt6buc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olwjt6buc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:maps" {...props}></Icon>
