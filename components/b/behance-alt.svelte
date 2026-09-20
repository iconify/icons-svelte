<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovb3_79qw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovb3_79qw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:behance-alt" {...props}></Icon>
