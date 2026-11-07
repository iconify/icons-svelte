<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmw0msqap.css';
import '../../css/j/jbgenzzof.css';
import '../../css/p/p09aqjb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bmw0msqap"/><path class="jbgenzzof"/><path class="p09aqjb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:inbox-out-bold" {...props}></Icon>
