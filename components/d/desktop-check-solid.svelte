<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th5wqpzfa.css';
import '../../css/a/ac63k3-ur.css';
import '../../css/h/h5cwullwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="th5wqpzfa"/><path clip-rule="evenodd" class="ac63k3-ur"/><path class="h5cwullwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:desktop-check-solid" {...props}></Icon>
