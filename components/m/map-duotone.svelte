<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1_6apbah.css';
import '../../css/d/dnw8ephhm.css';
import '../../css/c/cdkh7bjct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n1_6apbah"/><path class="dnw8ephhm"/><circle class="cdkh7bjct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:map-duotone" {...props}></Icon>
