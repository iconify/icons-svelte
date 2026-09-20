<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp4vkvb7i.css';
import '../../css/q/quusr8xpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zp4vkvb7i"/><path clip-rule="evenodd" class="quusr8xpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:erase-24" {...props}></Icon>
