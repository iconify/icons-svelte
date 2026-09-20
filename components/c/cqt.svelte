<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf5guvb6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qf5guvb6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cqt" {...props}></Icon>
