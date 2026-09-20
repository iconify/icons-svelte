<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q254hsbwh.css';
import '../../css/q/qjavm0bgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q254hsbwh"/><path class="qjavm0bgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:medical-house" {...props}></Icon>
