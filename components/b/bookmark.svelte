<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1utpacju.css';
import '../../css/q/qeh8d-bue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1utpacju"/><path class="qeh8d-bue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:bookmark" {...props}></Icon>
