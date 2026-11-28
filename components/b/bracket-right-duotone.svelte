<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be-0ib18l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="be-0ib18l primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bracket-right-duotone" {...props}></Icon>
