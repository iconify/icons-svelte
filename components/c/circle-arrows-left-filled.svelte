<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlt-fkb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qlt-fkb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:circle-arrows-left-filled" {...props}></Icon>
