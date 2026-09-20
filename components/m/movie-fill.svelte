<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o90fnvbiu.css';
import '../../css/q/qy0a994nu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o90fnvbiu"/><path class="qy0a994nu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:movie-fill" {...props}></Icon>
