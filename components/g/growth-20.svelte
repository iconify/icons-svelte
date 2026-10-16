<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmle-2ous.css';
import '../../css/y/yi354_nqc.css';
import '../../css/v/v7fhe39su.css';
import '../../css/y/yct5lw59k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nmle-2ous"/><path class="yi354_nqc"/><path class="v7fhe39su"/><path class="yct5lw59k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:growth-20" {...props}></Icon>
