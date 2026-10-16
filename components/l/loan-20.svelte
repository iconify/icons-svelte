<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbd146bio.css';
import '../../css/o/os3zlpkkp.css';
import '../../css/k/kf8qud5kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nbd146bio"/><path class="os3zlpkkp"/><path class="kf8qud5kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:loan-20" {...props}></Icon>
