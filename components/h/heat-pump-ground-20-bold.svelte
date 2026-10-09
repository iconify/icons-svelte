<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huo95kxbo.css';
import '../../css/t/txu8yubls.css';
import '../../css/a/arzvezb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="huo95kxbo"/><path class="txu8yubls"/><path class="arzvezb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-pump-ground-20-bold" {...props}></Icon>
