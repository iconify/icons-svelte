<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjd-bqb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjd-bqb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:medical-flask-filled" {...props}></Icon>
